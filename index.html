import React, { useState, useEffect } from 'react';
import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card"
import { Input } from "@/components/ui/input"
import { Label } from "@/components/ui/label"
import { Select, SelectContent, SelectItem, SelectTrigger, SelectValue } from "@/components/ui/select"
import { ScrollArea } from "@/components/ui/scroll-area"

const AutomationROICalculator = () => {
  const [automationType, setAutomationType] = useState('');
  const [timeSavedPerWeek, setTimeSavedPerWeek] = useState(9);
  const [hourlyRate, setHourlyRate] = useState(50);
  const [implementationCost, setImplementationCost] = useState(15000);
  const [maintenanceCostPerMonth, setMaintenanceCostPerMonth] = useState(200);
  const [results, setResults] = useState({
    weeklySavings: 0,
    monthlySavings: 0,
    annualSavings: 0,
    firstYearROI: 0,
    subsequentYearsROI: 0,
    fiveYearValue: 0
  });

  const automationTypes = [
    "Client Onboarding",
    "Client Success Management",
    "Call Qualification",
    "Internal Updates and ClickUp Task Management",
    "Sending SOPs to Team Members",
    "Client Acquisition",
    "Client Fulfillment",
    "Client Retention and LTV",
    "Client Referral Network and Communication",
    "Creating Personalized Assets for Leads and Internal Team",
    "Content Creation",
    "Ad Creation",
    "Ad Copy Creation",
    "Funnel Building",
    "Copywriting for the Funnel",
    "Automated Outreach Systems",
    "Automated Cold DM Systems",
    "Automated DM Setting with DM Setters and VAs",
    "VA Management",
    "DM Setter Management",
    "YouTube Content Creation Process A-Z",
    "Automating CRM Management, Pipelines, and Workflows",
    "Automating Invoicing",
    "Automated Tracking on UTM Sources from Website Clicks",
    "Automating Tracking for Ads",
    "Automating Tracking for UTM Sources from Social Media Opt-ins",
    "Automated Lead Magnet Based Funnels with Assets",
    "Other"
  ];

  useEffect(() => {
    calculateROI();
  }, [timeSavedPerWeek, hourlyRate, implementationCost, maintenanceCostPerMonth]);

  const calculateROI = () => {
    const weeklySavings = timeSavedPerWeek * hourlyRate;
    const monthlySavings = weeklySavings * 4;
    const annualSavings = weeklySavings * 52;
    const annualMaintenanceCost = maintenanceCostPerMonth * 12;

    const firstYearBenefit = annualSavings;
    const firstYearCost = implementationCost + annualMaintenanceCost;
    const firstYearNetBenefit = firstYearBenefit - firstYearCost;
    const firstYearROI = (firstYearNetBenefit / firstYearCost) * 100;

    const subsequentYearsNetBenefit = annualSavings - annualMaintenanceCost;
    const subsequentYearsROI = (subsequentYearsNetBenefit / annualMaintenanceCost) * 100;

    const fiveYearValue = (annualSavings * 5) - implementationCost - (annualMaintenanceCost * 5);

    setResults({
      weeklySavings,
      monthlySavings,
      annualSavings,
      firstYearROI,
      subsequentYearsROI,
      fiveYearValue
    });
  };

  return (
    <Card className="w-full max-w-2xl mx-auto">
      <CardHeader>
        <CardTitle>Customized Automation ROI Calculator</CardTitle>
      </CardHeader>
      <CardContent>
        <div className="grid grid-cols-2 gap-4">
          <div className="col-span-2">
            <Label htmlFor="automationType">Type of Automated Process</Label>
            <Select onValueChange={setAutomationType} defaultValue={automationType}>
              <SelectTrigger id="automationType">
                <SelectValue placeholder="Select process type" />
              </SelectTrigger>
              <SelectContent>
                <ScrollArea className="h-[200px]">
                  {automationTypes.map((type, index) => (
                    <SelectItem key={index} value={type.toLowerCase().replace(/ /g, '-')}>
                      {type}
                    </SelectItem>
                  ))}
                </ScrollArea>
              </SelectContent>
            </Select>
          </div>
          <div>
            <Label htmlFor="timeSaved">Time Saved Per Week (hours)</Label>
            <Input
              id="timeSaved"
              type="number"
              value={timeSavedPerWeek}
              onChange={(e) => setTimeSavedPerWeek(Number(e.target.value))}
            />
          </div>
          <div>
            <Label htmlFor="hourlyRate">Hourly Rate ($)</Label>
            <Input
              id="hourlyRate"
              type="number"
              value={hourlyRate}
              onChange={(e) => setHourlyRate(Number(e.target.value))}
            />
          </div>
          <div>
            <Label htmlFor="implementationCost">Implementation Cost ($)</Label>
            <Input
              id="implementationCost"
              type="number"
              value={implementationCost}
              onChange={(e) => setImplementationCost(Number(e.target.value))}
            />
          </div>
          <div>
            <Label htmlFor="maintenanceCost">Monthly Maintenance Cost ($)</Label>
            <Input
              id="maintenanceCost"
              type="number"
              value={maintenanceCostPerMonth}
              onChange={(e) => setMaintenanceCostPerMonth(Number(e.target.value))}
            />
          </div>
        </div>
        
        <div className="mt-6">
          <h3 className="text-lg font-semibold">Results for {automationType ? automationType.replace(/-/g, ' ') : 'selected process'}</h3>
          <p>Weekly Savings: ${results.weeklySavings.toFixed(2)}</p>
          <p>Monthly Savings: ${results.monthlySavings.toFixed(2)}</p>
          <p>Annual Savings: ${results.annualSavings.toFixed(2)}</p>
          <p>First Year ROI: {results.firstYearROI.toFixed(2)}%</p>
          <p>Subsequent Years ROI: {results.subsequentYearsROI.toFixed(2)}%</p>
          <p>5-Year Value: ${results.fiveYearValue.toFixed(2)}</p>
        </div>
      </CardContent>
    </Card>
  );
};

export default AutomationROICalculator;
